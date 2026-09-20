<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn3zg7bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn3zg7bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-ski" {...props}></Icon>
