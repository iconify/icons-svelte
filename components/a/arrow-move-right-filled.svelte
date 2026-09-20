<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1uo-p2gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1uo-p2gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-move-right-filled" {...props}></Icon>
