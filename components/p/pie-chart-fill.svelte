<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc08s7b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pc08s7b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pie-chart-fill" {...props}></Icon>
