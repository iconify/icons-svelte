<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ens04999i.css';
import '../../css/n/n_xfstkmc.css';
import '../../css/h/h03pgbcln.css';
import '../../css/m/mntmc0b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ens04999i"/><path class="n_xfstkmc"/><path class="h03pgbcln"/><path class="mntmc0b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-open" {...props}></Icon>
