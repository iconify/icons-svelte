<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztmoi2_at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ztmoi2_at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:anaconda" {...props}></Icon>
