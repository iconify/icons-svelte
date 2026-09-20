<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifct9_bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifct9_bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-right-thick" {...props}></Icon>
