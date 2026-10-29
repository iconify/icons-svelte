<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ejrauv4gk.css';
import '../../css/h/hadl-ib6c.css';
import '../../css/x/xfjk5rbmg.css';
import '../../css/u/uhjj-5r8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ejrauv4gk"/><path class="hadl-ib6c wm-a"/><path class="wm-k xfjk5rbmg"/><path class="uhjj-5r8y wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-image-sketch" {...props}></Icon>
