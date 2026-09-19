<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4gqgybhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="k4gqgybhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:eye-drop" {...props}></Icon>
