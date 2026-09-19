<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l9_wagkcs.css';
import '../../css/w/wzd_ul5ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l9_wagkcs"/><path clip-rule="evenodd" class="wzd_ul5ss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contraceptive-diaphragm-outline-24px" {...props}></Icon>
