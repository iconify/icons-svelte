<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikc3oob9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ikc3oob9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pinterest-outlined" {...props}></Icon>
