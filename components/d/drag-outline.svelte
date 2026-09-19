<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gupt5drld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gupt5drld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:drag-outline" {...props}></Icon>
