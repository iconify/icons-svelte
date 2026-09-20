<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tllzjacdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tllzjacdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-pos-cog-outline" {...props}></Icon>
