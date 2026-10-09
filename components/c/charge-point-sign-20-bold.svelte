<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti01b-i2m.css';
import '../../css/y/yyjf3gxzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ti01b-i2m"/><path class="yyjf3gxzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charge-point-sign-20-bold" {...props}></Icon>
