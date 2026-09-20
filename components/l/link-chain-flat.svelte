<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8yyz4_qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k8yyz4_qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:link-chain-flat" {...props}></Icon>
