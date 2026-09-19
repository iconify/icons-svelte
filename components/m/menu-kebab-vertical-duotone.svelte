<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snthn3bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snthn3bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-vertical-duotone" {...props}></Icon>
