<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwbwyza6z.css';
import '../../css/w/wo_81unih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwbwyza6z"/><path class="wo_81unih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-broken-bold-duotone" {...props}></Icon>
