<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlknw_bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nlknw_bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:missed-call-solid" {...props}></Icon>
