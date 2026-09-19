<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbu_oejkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbu_oejkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:close-sidebar-alt-outline" {...props}></Icon>
