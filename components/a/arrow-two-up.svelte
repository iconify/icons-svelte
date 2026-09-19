<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h56kjmbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="h56kjmbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-two-up" {...props}></Icon>
