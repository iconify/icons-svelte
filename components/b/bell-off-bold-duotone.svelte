<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8czseb2v.css';
import '../../css/u/uoo_ldb1e.css';
import '../../css/h/h03wxzbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8czseb2v"/><path class="uoo_ldb1e"/><path class="h03wxzbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-off-bold-duotone" {...props}></Icon>
