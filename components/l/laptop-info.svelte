<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwr0xrb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwr0xrb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:laptop-info" {...props}></Icon>
