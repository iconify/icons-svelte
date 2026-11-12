<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_wo_pbay.css';
import '../../css/i/imad5bjrh.css';
import '../../css/x/xi-cb_bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_wo_pbay"/><path class="imad5bjrh"/><path class="xi-cb_bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chorizard-dark" {...props}></Icon>
