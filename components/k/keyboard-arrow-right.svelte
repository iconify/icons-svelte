<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi9efiblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi9efiblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-arrow-right" {...props}></Icon>
