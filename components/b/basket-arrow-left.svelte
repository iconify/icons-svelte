<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufvqhk53l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ufvqhk53l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:basket-arrow-left" {...props}></Icon>
