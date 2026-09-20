<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzj5vab1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzj5vab1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:arrow-down" {...props}></Icon>
