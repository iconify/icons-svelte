<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf_l1cpme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kf_l1cpme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bulb-outlined" {...props}></Icon>
