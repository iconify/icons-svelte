<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdgey5bpj.css';
import '../../css/z/zxi_dh3ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdgey5bpj"/><path class="zxi_dh3ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:barcode" {...props}></Icon>
