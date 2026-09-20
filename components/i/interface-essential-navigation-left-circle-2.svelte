<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uckz_1f4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uckz_1f4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-navigation-left-circle-2" {...props}></Icon>
