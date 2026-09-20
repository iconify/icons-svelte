<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjzmo6ptv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jjzmo6ptv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:payment-cash-out-3-solid" {...props}></Icon>
