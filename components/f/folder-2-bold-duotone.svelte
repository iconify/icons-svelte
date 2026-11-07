<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pteai7udj.css';
import '../../css/k/kvtxzidpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pteai7udj"/><path class="kvtxzidpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-2-bold-duotone" {...props}></Icon>
