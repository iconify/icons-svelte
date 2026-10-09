<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erj_vhb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erj_vhb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lampada-parete" {...props}></Icon>
