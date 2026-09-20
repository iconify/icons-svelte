<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwqn_bbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwqn_bbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-up-right-fill" {...props}></Icon>
