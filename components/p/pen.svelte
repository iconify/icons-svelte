<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/covvo99ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="covvo99ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:pen" {...props}></Icon>
