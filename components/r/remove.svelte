<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4z93u2al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="c4z93u2al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:remove" {...props}></Icon>
