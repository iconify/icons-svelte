<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q84g-bbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q84g-bbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-circle" {...props}></Icon>
