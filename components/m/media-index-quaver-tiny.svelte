<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3-qilbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n3-qilbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-index-quaver-tiny" {...props}></Icon>
