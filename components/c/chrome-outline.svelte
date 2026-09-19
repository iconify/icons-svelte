<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptc2ntoas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ptc2ntoas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:chrome-outline" {...props}></Icon>
