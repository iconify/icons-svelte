<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jck0vfbad.css';
import '../../css/u/u2p_6-b8n.css';
import '../../css/t/t74-6o1oe.css';
import '../../css/i/iuwke7bvt.css';
import '../../css/c/cq01zfbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jck0vfbad"/><circle class="u2p_6-b8n"/><circle class="t74-6o1oe"/><circle class="iuwke7bvt"/><path class="cq01zfbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-assistant" {...props}></Icon>
