<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr9hgly8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cr9hgly8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cellular-network-lte-solid" {...props}></Icon>
