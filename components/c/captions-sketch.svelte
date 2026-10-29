<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/twxqgt_ca.css';
import '../../css/y/yrlyq9bep.css';
import '../../css/h/hf_ak9q6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="twxqgt_ca wm-k"/><path class="wm-k yrlyq9bep"/><path class="hf_ak9q6y wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:captions-sketch" {...props}></Icon>
