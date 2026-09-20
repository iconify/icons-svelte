<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk9l67bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sk9l67bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dflow-light" {...props}></Icon>
