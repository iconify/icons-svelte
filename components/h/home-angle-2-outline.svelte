<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swvwx0b5q.css';
import '../../css/q/qzj3lla5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swvwx0b5q"/><path clip-rule="evenodd" class="qzj3lla5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-angle-2-outline" {...props}></Icon>
