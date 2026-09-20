<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_nsdrg7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_nsdrg7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:business-hierarchy" {...props}></Icon>
