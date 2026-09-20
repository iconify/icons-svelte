<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y831ulb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y831ulb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:food-turkey" {...props}></Icon>
