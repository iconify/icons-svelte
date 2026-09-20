<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6ukjobns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6ukjobns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:business-pick-user" {...props}></Icon>
