<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u62fcjb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u62fcjb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:environment-outline" {...props}></Icon>
