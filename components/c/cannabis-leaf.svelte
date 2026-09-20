<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7ex8kgyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ex8kgyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:cannabis-leaf" {...props}></Icon>
