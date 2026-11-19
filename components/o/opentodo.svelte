<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4p_lbhmc.css';
import '../../css/h/hrou1ov-o.css';
import '../../css/j/j92vpxe-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="c4p_lbhmc"/><path class="hrou1ov-o"/><path class="j92vpxe-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentodo" {...props}></Icon>
