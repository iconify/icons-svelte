<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8x9iqblc.css';
import '../../css/p/plqc46bvd.css';
import '../../css/d/dvj1g-bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v8x9iqblc"/><path class="plqc46bvd"/><path class="dvj1g-bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lock" {...props}></Icon>
