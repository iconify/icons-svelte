<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_qdmlbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="u_qdmlbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pause-button" {...props}></Icon>
