<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so2_osfrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="so2_osfrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:node-expand-outlined" {...props}></Icon>
