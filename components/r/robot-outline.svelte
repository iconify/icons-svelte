<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx6o3lh-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hx6o3lh-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:robot-outline" {...props}></Icon>
