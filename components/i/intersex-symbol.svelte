<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfmcfcxib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qfmcfcxib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:intersex-symbol" {...props}></Icon>
