<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcib6zbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcib6zbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ink-minus-outline" {...props}></Icon>
