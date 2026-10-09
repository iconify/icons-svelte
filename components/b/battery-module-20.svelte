<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m62_8ratf.css';
import '../../css/l/lrevnvbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m62_8ratf"/><path class="lrevnvbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-module-20" {...props}></Icon>
