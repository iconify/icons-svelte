<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fziugkfyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fziugkfyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:other-reading" {...props}></Icon>
