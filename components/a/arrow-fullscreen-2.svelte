<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1qm32gsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="c1qm32gsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-fullscreen-2" {...props}></Icon>
