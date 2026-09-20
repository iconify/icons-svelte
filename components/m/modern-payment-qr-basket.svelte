<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/oxb_gvhjw.css';
import '../../css/g/g3c_gibpm.css';
import '../../css/v/vlfia-hui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="oxb_gvhjw"/><path class="g3c_gibpm"/><path class="vlfia-hui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:modern-payment-qr-basket" {...props}></Icon>
