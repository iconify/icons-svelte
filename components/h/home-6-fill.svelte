<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flbl-5mpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flbl-5mpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-6-fill" {...props}></Icon>
