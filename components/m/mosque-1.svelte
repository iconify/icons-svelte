<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bmdpr8b1x.css';
import '../../css/i/iysxbi1pg.css';
import '../../css/v/vhnu_io7d.css';
import '../../css/r/rh3b5mb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bmdpr8b1x"/><path class="iysxbi1pg"/><path class="vhnu_io7d"/><path class="rh3b5mb2s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mosque-1" {...props}></Icon>
