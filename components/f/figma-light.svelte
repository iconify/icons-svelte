<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbec9fl-o.css';
import '../../css/q/qcxpfgbgl.css';
import '../../css/i/i-k_57oki.css';
import '../../css/e/eux5nikfz.css';
import '../../css/y/y0zkh2w_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wbec9fl-o"/><path class="qcxpfgbgl"/><circle class="i-k_57oki"/><path class="eux5nikfz"/><path class="y0zkh2w_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:figma-light" {...props}></Icon>
