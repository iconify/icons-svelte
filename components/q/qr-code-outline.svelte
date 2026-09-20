<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3cvb4ysw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r3cvb4ysw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:qr-code-outline" {...props}></Icon>
