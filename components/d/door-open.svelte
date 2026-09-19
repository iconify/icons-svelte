<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws7kkc8ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ws7kkc8ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:door-open" {...props}></Icon>
