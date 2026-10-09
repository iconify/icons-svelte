<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k25wbcbbf.css';
import '../../css/x/x2ixy0bli.css';
import '../../css/t/tgh03o3xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k25wbcbbf"/><path class="x2ixy0bli"/><path class="tgh03o3xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ozone-48" {...props}></Icon>
