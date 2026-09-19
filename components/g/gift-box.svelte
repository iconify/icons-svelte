<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkg_6kiod.css';
import '../../css/y/yff_o1a8n.css';
import '../../css/a/aj04idbfe.css';
import '../../css/c/csr-bnj3w.css';
import '../../css/u/uqeth4bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vkg_6kiod"/><path clip-rule="evenodd" class="yff_o1a8n"/><path clip-rule="evenodd" class="aj04idbfe"/><path clip-rule="evenodd" class="csr-bnj3w"/><path clip-rule="evenodd" class="uqeth4bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:gift-box" {...props}></Icon>
