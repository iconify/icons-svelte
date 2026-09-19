<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y78v_dbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="y78v_dbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:music" {...props}></Icon>
