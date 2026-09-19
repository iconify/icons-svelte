<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcosuhb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":408};
const content = `<path class="dcosuhb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:navigation" {...props}></Icon>
