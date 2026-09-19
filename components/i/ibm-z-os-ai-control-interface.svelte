<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j60zr3b4x.css';
import '../../css/i/ireqoewfc.css';
import '../../css/c/c7gfsbb7m.css';
import '../../css/t/t1-idpbjp.css';
import '../../css/q/qk4ai5xli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="j60zr3b4x"/><path class="ireqoewfc"/><circle class="c7gfsbb7m"/><path class="t1-idpbjp"/><path class="qk4ai5xli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-z-os-ai-control-interface" {...props}></Icon>
