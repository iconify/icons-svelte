<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdf1uzbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdf1uzbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-pin" {...props}></Icon>
