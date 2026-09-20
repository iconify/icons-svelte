<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_kltstqp.css';
import '../../css/s/smm_-b_wm.css';
import '../../css/d/dzs_rab9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_kltstqp"/><path class="smm_-b_wm"/><path class="dzs_rab9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:desktop-duotone" {...props}></Icon>
