<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usa70rbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usa70rbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pliers" {...props}></Icon>
