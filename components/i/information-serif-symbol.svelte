<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4ltb_bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4ltb_bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:information-serif-symbol" {...props}></Icon>
