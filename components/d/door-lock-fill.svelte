<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2h2y-e_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2h2y-e_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:door-lock-fill" {...props}></Icon>
