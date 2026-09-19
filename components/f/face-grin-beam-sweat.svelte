<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc78wxt7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oc78wxt7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-grin-beam-sweat" {...props}></Icon>
