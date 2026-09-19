<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/xglklabzt.css';
import '../../css/d/dg-z_9bth.css';
import '../../css/v/vw_4rdbwn.css';
import '../../css/q/q2on0eeef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="xglklabzt"/><path class="dg-z_9bth"/><path class="vw_4rdbwn"/><path class="q2on0eeef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:no-dollars-outline" {...props}></Icon>
