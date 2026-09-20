<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dayz5c4na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dayz5c4na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:memory" {...props}></Icon>
