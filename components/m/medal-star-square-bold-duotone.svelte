<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv2msx5_t.css';
import '../../css/v/v5fufdeal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv2msx5_t"/><path clip-rule="evenodd" class="v5fufdeal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-square-bold-duotone" {...props}></Icon>
