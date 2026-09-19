<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmsij2f1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmsij2f1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-arrow-round-down" {...props}></Icon>
