<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it2o87jea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it2o87jea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-horizontal-duotone" {...props}></Icon>
