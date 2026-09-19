<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z61ng_bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z61ng_bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rectangle-horizontal" {...props}></Icon>
