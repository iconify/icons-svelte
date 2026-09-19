<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz65g_ywp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz65g_ywp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-hail" {...props}></Icon>
