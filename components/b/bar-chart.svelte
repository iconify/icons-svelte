<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ely0vkp6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ely0vkp6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bar-chart" {...props}></Icon>
