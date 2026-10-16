<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybbuh2wlg.css';
import '../../css/v/vz5gujb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ybbuh2wlg"/><path class="vz5gujb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-price-20-bold" {...props}></Icon>
