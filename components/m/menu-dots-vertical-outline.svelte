<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pkxx7pbdp.css';
import '../../css/h/hp_pc2tmb.css';
import '../../css/t/tmnkdvnlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="pkxx7pbdp"/><path class="hp_pc2tmb"/><path class="tmnkdvnlf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-vertical-outline" {...props}></Icon>
