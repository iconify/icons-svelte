<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-st2-zet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="n-st2-zet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cloud-rain-heavy-rain" {...props}></Icon>
