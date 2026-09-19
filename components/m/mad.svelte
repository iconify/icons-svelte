<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gshe_di8n.css';
import '../../css/s/s1q8lcb1s.css';
import '../../css/i/ifwem2bpq.css';
import '../../css/x/xuh70gfac.css';
import '../../css/u/un96hmbbz.css';
import '../../css/r/r_oxw7o-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="s1q8lcb1s"/><path class="ifwem2bpq"/><path class="xuh70gfac"/><path class="un96hmbbz"/><path class="r_oxw7o-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mad" {...props}></Icon>
