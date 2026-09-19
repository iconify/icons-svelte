<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyjiv_0rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyjiv_0rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chart-mixed-outline" {...props}></Icon>
