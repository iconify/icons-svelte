<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1r_d5pul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1r_d5pul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-switch-fill" {...props}></Icon>
