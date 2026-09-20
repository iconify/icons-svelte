<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp38xqa3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp38xqa3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:phone-lock-line" {...props}></Icon>
