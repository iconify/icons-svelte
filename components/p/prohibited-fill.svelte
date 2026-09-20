<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1n-77d_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1n-77d_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:prohibited-fill" {...props}></Icon>
