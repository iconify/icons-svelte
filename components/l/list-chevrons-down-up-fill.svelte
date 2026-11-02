<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhz_pd5hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhz_pd5hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-chevrons-down-up-fill" {...props}></Icon>
