<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gshe_di8n.css';
import '../../css/v/vpfegd3_c.css';
import '../../css/a/akde-jumm.css';
import '../../css/u/un96hmbbz.css';
import '../../css/l/lzd_sub0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="vpfegd3_c"/><path class="akde-jumm"/><path class="un96hmbbz"/><path class="lzd_sub0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nervous" {...props}></Icon>
