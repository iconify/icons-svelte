<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5ku-ztwy.css';
import '../../css/i/ib2bxjbcn.css';
import '../../css/m/ma62eabge.css';
import '../../css/a/aqp8o2-2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5ku-ztwy"/><path class="ib2bxjbcn"/><path class="ma62eabge"/><path class="aqp8o2-2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homescreen-hero-dark" {...props}></Icon>
