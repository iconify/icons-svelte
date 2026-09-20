<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_su40b-o.css';
import '../../css/a/a46a2oiqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r_su40b-o"/><path class="a46a2oiqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:casino" {...props}></Icon>
