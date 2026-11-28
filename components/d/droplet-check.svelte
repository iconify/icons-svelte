<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4f8m2rpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4f8m2rpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:droplet-check" {...props}></Icon>
