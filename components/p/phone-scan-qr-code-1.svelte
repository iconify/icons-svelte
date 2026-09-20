<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv2c330tb.css';
import '../../css/o/of89spbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jv2c330tb"/><path class="of89spbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:phone-scan-qr-code-1" {...props}></Icon>
