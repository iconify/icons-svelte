<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d63uw4pmm.css';
import '../../css/v/vu18-_bab.css';
import '../../css/l/lg9shfpyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d63uw4pmm"/><path class="vu18-_bab"/><path class="lg9shfpyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:facemask-circle-outline" {...props}></Icon>
