<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnn5m5bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xnn5m5bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:car-side-solid" {...props}></Icon>
