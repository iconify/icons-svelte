<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ou-ck_tfg.css';
import '../../css/t/twn_ioblf.css';
import '../../css/l/lgr3-yo0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ou-ck_tfg"/><path class="twn_ioblf"/><circle class="lgr3-yo0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:notification-duotone" {...props}></Icon>
