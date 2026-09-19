<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l47w35-sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="l47w35-sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:fire-hydrant" {...props}></Icon>
