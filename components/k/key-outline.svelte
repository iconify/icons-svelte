<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2kapd5nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p2kapd5nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:key-outline" {...props}></Icon>
