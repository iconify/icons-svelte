<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy2l7ab8f.css';
import '../../css/i/i6ux3gi0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy2l7ab8f"/><path class="i6ux3gi0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:incoming-call-rounded-outline" {...props}></Icon>
