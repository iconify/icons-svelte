<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlrw7obei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="mlrw7obei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:dice-5" {...props}></Icon>
