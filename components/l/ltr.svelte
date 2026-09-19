<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly93z8bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ly93z8bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:ltr" {...props}></Icon>
