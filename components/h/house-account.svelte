<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4ifvnbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4ifvnbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-account" {...props}></Icon>
