<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wpb2ui7ty.css';
import '../../css/b/b6650acng.css';
import '../../css/v/v7yy21tjl.css';
import '../../css/w/wriov4-rf.css';
import '../../css/p/psa1kob_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wpb2ui7ty"/><path class="b6650acng"/><path class="v7yy21tjl"/><path class="wriov4-rf"/><path class="psa1kob_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:luggage-duotone" {...props}></Icon>
