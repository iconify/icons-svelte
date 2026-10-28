<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1c3kp_ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1c3kp_ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:netto" {...props}></Icon>
