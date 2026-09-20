<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwp5elblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwp5elblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:newgrounds" {...props}></Icon>
