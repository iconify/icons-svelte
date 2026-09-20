<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flzduy9-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flzduy9-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ring" {...props}></Icon>
