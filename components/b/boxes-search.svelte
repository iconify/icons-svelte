<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky8-f3bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky8-f3bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:boxes-search" {...props}></Icon>
