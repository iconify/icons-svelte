<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le-kwnbxs.css';
import '../../css/v/ven4ce_vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="le-kwnbxs"/><path class="ven4ce_vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:eye-blocked" {...props}></Icon>
