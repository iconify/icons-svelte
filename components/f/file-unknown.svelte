<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1zkwsbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l1zkwsbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-unknown" {...props}></Icon>
