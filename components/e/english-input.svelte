<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj8g4n60a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj8g4n60a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:english-input" {...props}></Icon>
