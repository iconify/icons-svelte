<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_sfaibgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_sfaibgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:plug-1" {...props}></Icon>
