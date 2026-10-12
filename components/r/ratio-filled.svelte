<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz_m0fb4u.css';
import '../../css/y/yuu2iyljg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz_m0fb4u"/><path clip-rule="evenodd" class="yuu2iyljg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ratio-filled" {...props}></Icon>
