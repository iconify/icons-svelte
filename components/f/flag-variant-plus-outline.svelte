<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azme87jwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azme87jwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant-plus-outline" {...props}></Icon>
