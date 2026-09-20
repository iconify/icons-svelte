<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpmv5nbra.css';
import '../../css/h/h5bun4ehf.css';
import '../../css/h/hm6t7gb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qpmv5nbra"/><path class="h5bun4ehf"/><path class="hm6t7gb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:phone-off-2" {...props}></Icon>
