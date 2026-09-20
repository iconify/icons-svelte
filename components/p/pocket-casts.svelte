<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_jlxib2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_jlxib2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pocket-casts" {...props}></Icon>
