<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgissgbda.css';
import '../../css/w/w1wl29bmf.css';
import '../../css/c/ckoc0pbbx.css';
import '../../css/x/x4f46-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgissgbda"/><path class="w1wl29bmf"/><path class="ckoc0pbbx"/><path class="x4f46-b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-badge-bold-duotone" {...props}></Icon>
