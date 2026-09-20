<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mnsucibnt.css';
import '../../css/a/ail7rketm.css';
import '../../css/w/w11gq4btp.css';
import '../../css/h/hq1qt2gln.css';
import '../../css/z/zolbpybdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mnsucibnt"/><path class="ail7rketm"/><path clip-rule="evenodd" class="w11gq4btp"/><path clip-rule="evenodd" class="hq1qt2gln"/><path clip-rule="evenodd" class="zolbpybdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:closet-bold" {...props}></Icon>
