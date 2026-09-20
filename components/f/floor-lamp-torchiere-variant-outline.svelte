<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcd1rsl6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcd1rsl6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floor-lamp-torchiere-variant-outline" {...props}></Icon>
