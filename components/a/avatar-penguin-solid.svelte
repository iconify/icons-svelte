<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwq5c0b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwq5c0b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-penguin-solid" {...props}></Icon>
