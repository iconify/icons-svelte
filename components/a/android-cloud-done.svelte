<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv2lcubgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hv2lcubgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-cloud-done" {...props}></Icon>
