<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg6z1ub6a.css';
import '../../css/q/qtozvfikf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg6z1ub6a"/><path clip-rule="evenodd" class="qtozvfikf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-plus-bold-duotone" {...props}></Icon>
