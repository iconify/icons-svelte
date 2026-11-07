<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl-98b13w.css';
import '../../css/c/cq-7z0vfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl-98b13w"/><path clip-rule="evenodd" class="cq-7z0vfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-security-bold-duotone" {...props}></Icon>
