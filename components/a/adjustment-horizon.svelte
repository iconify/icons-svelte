<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr_oih2cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="hr_oih2cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:adjustment-horizon" {...props}></Icon>
