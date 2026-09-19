<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux0tzvb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux0tzvb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:caret-sort-outline" {...props}></Icon>
