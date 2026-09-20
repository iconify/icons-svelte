<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv0_sebma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hv0_sebma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-love" {...props}></Icon>
