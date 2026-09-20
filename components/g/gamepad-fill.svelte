<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciyf57kyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ciyf57kyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gamepad-fill" {...props}></Icon>
