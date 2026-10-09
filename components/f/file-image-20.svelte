<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-g74icta.css';
import '../../css/m/mh0v5urfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="mh0v5urfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-image-20" {...props}></Icon>
