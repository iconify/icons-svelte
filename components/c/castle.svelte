<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf875nbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf875nbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:castle" {...props}></Icon>
