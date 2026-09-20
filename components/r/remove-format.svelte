<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec-h0tbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ec-h0tbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:remove-format" {...props}></Icon>
