<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4xl15bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4xl15bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kit" {...props}></Icon>
