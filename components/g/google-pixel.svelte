<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiycw97dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiycw97dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:google-pixel" {...props}></Icon>
