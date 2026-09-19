<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6gvdlb7i.css';
import '../../css/s/soi_5_bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6gvdlb7i"/><path class="soi_5_bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-left-stroke-square-filled" {...props}></Icon>
