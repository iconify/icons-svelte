<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joyy5sbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="joyy5sbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:droplet-off" {...props}></Icon>
