<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0_ybkue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dt0_ybkue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:filter-outlined" {...props}></Icon>
