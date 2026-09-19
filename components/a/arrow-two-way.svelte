<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik5cx86xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="ik5cx86xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-two-way" {...props}></Icon>
