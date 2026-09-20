<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orvawkb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orvawkb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:megaphone" {...props}></Icon>
