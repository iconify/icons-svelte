<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqx3r_ngw.css';
import '../../css/o/o3p-r8q4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqx3r_ngw"/><path class="o3p-r8q4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hospital-bold-duotone" {...props}></Icon>
