<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8pd_ylov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n8pd_ylov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:home-filled" {...props}></Icon>
