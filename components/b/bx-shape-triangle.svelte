<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u79ntacah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u79ntacah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-shape-triangle" {...props}></Icon>
