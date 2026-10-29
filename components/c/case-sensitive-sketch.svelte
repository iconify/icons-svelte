<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/iv63f0bdx.css';
import '../../css/h/he7_nbbdh.css';
import '../../css/z/z_amcpmpe.css';
import '../../css/g/g_rss-mdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="iv63f0bdx wm-k"/><path class="he7_nbbdh wm-a"/><path class="wm-k z_amcpmpe"/><path class="g_rss-mdm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:case-sensitive-sketch" {...props}></Icon>
