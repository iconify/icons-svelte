<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw6-ov3tm.css';
import '../../css/l/liz26ccin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lw6-ov3tm"/><path class="liz26ccin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-picture-in-picture-active" {...props}></Icon>
