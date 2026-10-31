<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_bojubrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_bojubrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mountain-gloss" {...props}></Icon>
