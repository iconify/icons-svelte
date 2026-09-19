<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my91cbcgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="my91cbcgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-reload" {...props}></Icon>
