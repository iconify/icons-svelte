<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/xglklabzt.css';
import '../../css/o/or_e2fe0o.css';
import '../../css/b/bjbn9291n.css';
import '../../css/e/e-vhv53hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="xglklabzt"/><circle class="or_e2fe0o"/><circle class="bjbn9291n"/><path class="e-vhv53hm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:bitty-outline" {...props}></Icon>
