<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl1m2nbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kl1m2nbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:media-step-backward" {...props}></Icon>
