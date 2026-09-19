<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9iv86f0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9iv86f0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:barcode" {...props}></Icon>
