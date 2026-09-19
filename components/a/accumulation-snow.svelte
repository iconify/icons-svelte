<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx4b9vbux.css';
import '../../css/m/m24l3fbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dx4b9vbux"/><path class="m24l3fbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:accumulation-snow" {...props}></Icon>
