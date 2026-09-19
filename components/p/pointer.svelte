<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppb8sdobi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ppb8sdobi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:pointer" {...props}></Icon>
