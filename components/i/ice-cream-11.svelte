<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxtbdh8eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="sxtbdh8eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:ice-cream-11" {...props}></Icon>
