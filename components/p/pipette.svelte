<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7zxa8g-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7zxa8g-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pipette" {...props}></Icon>
