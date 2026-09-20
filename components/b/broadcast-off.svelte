<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_s-0n7ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_s-0n7ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:broadcast-off" {...props}></Icon>
