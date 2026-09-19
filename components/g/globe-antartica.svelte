<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yev1t9yns.css';
import '../../css/z/zv4wep4nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yev1t9yns"/><path class="zv4wep4nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-antartica" {...props}></Icon>
