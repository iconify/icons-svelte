<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruon_hbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ruon_hbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-information-circle-2" {...props}></Icon>
