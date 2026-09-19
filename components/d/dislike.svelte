<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz4zh1bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sz4zh1bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dislike" {...props}></Icon>
