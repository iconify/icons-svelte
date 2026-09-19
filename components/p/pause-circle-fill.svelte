<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzhm1sb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nzhm1sb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pause-circle-fill" {...props}></Icon>
