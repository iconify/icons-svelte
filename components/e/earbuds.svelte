<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pns9tc5hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pns9tc5hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:earbuds" {...props}></Icon>
