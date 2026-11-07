<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olusrszwm.css';
import '../../css/p/p5cc5fbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olusrszwm"/><path class="p5cc5fbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-2-outline" {...props}></Icon>
