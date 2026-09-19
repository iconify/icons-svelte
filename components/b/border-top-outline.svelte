<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snm29mb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="snm29mb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:border-top-outline" {...props}></Icon>
