<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4pp3eddj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4pp3eddj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kununu" {...props}></Icon>
