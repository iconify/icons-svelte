<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-w1iwbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-w1iwbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crop-5-4" {...props}></Icon>
