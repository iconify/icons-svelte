<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/r5qicdcsm.css';
import '../../css/w/wjl-5kbwl.css';
import '../../css/x/xyon_4mfc.css';
import '../../css/n/ny1qr-80o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r5qicdcsm"/><path class="wjl-5kbwl"/><circle class="xyon_4mfc"/><circle class="ny1qr-80o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:folder-git-2" {...props}></Icon>
