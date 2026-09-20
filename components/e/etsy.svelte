<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmcda7bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmcda7bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:etsy" {...props}></Icon>
