<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-ge2ebrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-ge2ebrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-squint-tears" {...props}></Icon>
