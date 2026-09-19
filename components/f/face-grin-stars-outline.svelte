<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s_ak5bbdo.css';
import '../../css/g/gxg0gv6fg.css';
import '../../css/i/ieosfnksq.css';
import '../../css/k/kdpnic1uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s_ak5bbdo"/><path class="gxg0gv6fg"/><path class="ieosfnksq"/><path class="kdpnic1uz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:face-grin-stars-outline" {...props}></Icon>
