<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3x3ckbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o3x3ckbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:reduce" {...props}></Icon>
