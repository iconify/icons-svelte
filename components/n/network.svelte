<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srsb_8zfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="srsb_8zfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:network" {...props}></Icon>
