<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6rl69b5y.css';
import '../../css/x/xaot8zbng.css';
import '../../css/u/uy28rnb-n.css';
import '../../css/d/d25mwn3tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6rl69b5y"/><path class="xaot8zbng"/><path class="uy28rnb-n"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-chart-outline" {...props}></Icon>
