<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg24ipbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg24ipbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-bar-increasing" {...props}></Icon>
