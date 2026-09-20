<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpppe-bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpppe-bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:biome" {...props}></Icon>
