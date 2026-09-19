<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2dfsxb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r2dfsxb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:alipay" {...props}></Icon>
