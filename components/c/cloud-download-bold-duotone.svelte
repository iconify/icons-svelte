<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg6z1ub6a.css';
import '../../css/z/zyax-g3ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg6z1ub6a"/><path clip-rule="evenodd" class="zyax-g3ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-download-bold-duotone" {...props}></Icon>
