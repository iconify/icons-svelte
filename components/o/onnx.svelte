<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trxm-hbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trxm-hbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:onnx" {...props}></Icon>
