<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0p4c2bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c0p4c2bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:fund-fill" {...props}></Icon>
