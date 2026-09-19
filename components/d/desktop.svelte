<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2u7zvnem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s2u7zvnem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:desktop" {...props}></Icon>
