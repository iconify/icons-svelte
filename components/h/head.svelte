<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiaumi8lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iiaumi8lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:head" {...props}></Icon>
