<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg0_1ub4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg0_1ub4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:indent-decrease" {...props}></Icon>
