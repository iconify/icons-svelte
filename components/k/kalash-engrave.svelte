<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fzlgrtb8q.css';
import '../../css/a/a5_vm_89c.css';
import '../../css/o/oi-opqu9k.css';
import '../../css/w/wq38gndli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fzlgrtb8q"/><path class="a5_vm_89c wm-shadow"/><path class="oi-opqu9k"/><path class="wq38gndli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:kalash-engrave" {...props}></Icon>
