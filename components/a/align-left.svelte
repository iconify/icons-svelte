<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h37_n9-5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="h37_n9-5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:align-left" {...props}></Icon>
