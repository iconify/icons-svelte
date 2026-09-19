<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_77jkb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_77jkb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chevron-sort-outline" {...props}></Icon>
