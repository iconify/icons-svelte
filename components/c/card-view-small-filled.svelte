<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_g_psdmk.css';
import '../../css/j/ji90m8bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="r_g_psdmk"/><path class="ji90m8bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:card-view-small-filled" {...props}></Icon>
