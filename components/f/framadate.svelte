<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpk98bbzf.css';
import '../../css/a/aekvfuqpv.css';
import '../../css/o/o6vxk8b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gpk98bbzf"/><path class="aekvfuqpv"/><path class="o6vxk8b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:framadate" {...props}></Icon>
