<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzzazwo4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rzzazwo4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:gateway-outline" {...props}></Icon>
