<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kfjxj683d.css';
import '../../css/z/zqs39fbjf.css';
import '../../css/o/okxvgrb-h.css';
import '../../css/g/gme1-c65h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kfjxj683d"/><path class="zqs39fbjf"/><path class="okxvgrb-h"/><path class="gme1-c65h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-alt-duotone" {...props}></Icon>
