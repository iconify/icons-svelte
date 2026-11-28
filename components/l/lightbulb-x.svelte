<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvxhy-pim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvxhy-pim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:lightbulb-x" {...props}></Icon>
