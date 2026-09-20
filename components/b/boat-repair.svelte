<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsk64_bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zsk64_bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:boat-repair" {...props}></Icon>
