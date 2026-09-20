<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4feqdlxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4feqdlxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant-outline" {...props}></Icon>
