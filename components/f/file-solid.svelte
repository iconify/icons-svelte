<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztmcp1b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ztmcp1b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-solid" {...props}></Icon>
