<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfc1urbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kfc1urbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:apple-outline" {...props}></Icon>
