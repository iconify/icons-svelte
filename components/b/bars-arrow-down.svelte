<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fameyv2xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fameyv2xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-arrow-down" {...props}></Icon>
