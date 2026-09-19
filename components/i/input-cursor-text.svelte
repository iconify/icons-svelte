<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1y6vhbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1y6vhbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:input-cursor-text" {...props}></Icon>
