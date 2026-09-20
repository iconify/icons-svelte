<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4m2uyb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d4m2uyb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-navigation-right-circle-2" {...props}></Icon>
