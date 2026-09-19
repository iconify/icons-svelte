<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf3gg-0xm.css';
import '../../css/r/rgz18cbgd.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="bf3gg-0xm clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 rgz18cbgd"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:link-line" {...props}></Icon>
