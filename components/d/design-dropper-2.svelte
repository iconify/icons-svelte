<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbtkdik_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tbtkdik_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-dropper-2" {...props}></Icon>
