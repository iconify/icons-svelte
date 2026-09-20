<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx-j32p0d.css';
import '../../css/a/ad3korw9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jx-j32p0d"/><path class="ad3korw9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-immunizations" {...props}></Icon>
