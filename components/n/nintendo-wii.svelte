<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crq2szbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crq2szbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nintendo-wii" {...props}></Icon>
