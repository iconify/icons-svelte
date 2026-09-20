<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z33w5xbvj.css';
import '../../css/t/tbq22ql4t.css';
import '../../css/l/l9zps-btr.css';
import '../../css/k/krip4lmfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z33w5xbvj"/><path class="tbq22ql4t"/><path class="l9zps-btr"/><path class="krip4lmfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-carousel" {...props}></Icon>
