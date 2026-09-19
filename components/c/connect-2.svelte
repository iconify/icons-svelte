<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf81sm_hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="rf81sm_hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:connect-2" {...props}></Icon>
