<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6t4w63sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6t4w63sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cart-outline" {...props}></Icon>
