<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms8v5kbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms8v5kbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bottle-wine-outline" {...props}></Icon>
