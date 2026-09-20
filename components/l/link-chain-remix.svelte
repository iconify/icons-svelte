<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp-5gabhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qp-5gabhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:link-chain-remix" {...props}></Icon>
