<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytjd3_bxd.css';
import '../../css/r/rj2mhcbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytjd3_bxd"/><path clip-rule="evenodd" class="rj2mhcbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:multiple-forward-right-bold-duotone" {...props}></Icon>
