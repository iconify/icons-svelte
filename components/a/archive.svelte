<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri-d8bcfx.css';
import '../../css/b/b7j_n5anm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ri-d8bcfx"/><path class="b7j_n5anm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:archive" {...props}></Icon>
