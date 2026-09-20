<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjbznwmxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjbznwmxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-lens-fill" {...props}></Icon>
