<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irf1ofbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irf1ofbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:column-outline" {...props}></Icon>
