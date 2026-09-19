<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rla7-lvwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rla7-lvwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-horizontal-duotone" {...props}></Icon>
