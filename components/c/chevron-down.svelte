<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp9-9q1-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp9-9q1-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chevron-down" {...props}></Icon>
