<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p25xc3b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p25xc3b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:legal" {...props}></Icon>
