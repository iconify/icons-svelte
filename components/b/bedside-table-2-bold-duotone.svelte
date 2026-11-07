<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5k33wnun.css';
import '../../css/z/zmr_0im2r.css';
import '../../css/l/laypnctxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s5k33wnun"/><path class="zmr_0im2r"/><path clip-rule="evenodd" class="laypnctxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bedside-table-2-bold-duotone" {...props}></Icon>
