<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6xu7ib6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c6xu7ib6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:printer-outline" {...props}></Icon>
