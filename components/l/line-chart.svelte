<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk1nlix-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk1nlix-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:line-chart" {...props}></Icon>
