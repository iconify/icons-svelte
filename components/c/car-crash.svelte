<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3hzk0bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="o3hzk0bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:car-crash" {...props}></Icon>
