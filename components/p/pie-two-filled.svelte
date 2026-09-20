<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7i2tnc_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d7i2tnc_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:pie-two-filled" {...props}></Icon>
