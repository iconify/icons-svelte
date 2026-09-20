<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgn3rcgnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgn3rcgnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-11" {...props}></Icon>
