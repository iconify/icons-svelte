<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aasc8vbxv.css';
import '../../css/f/fu7i_4vmt.css';
import '../../css/p/puyadibwf.css';
import '../../css/d/djxw08b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aasc8vbxv"/><path class="fu7i_4vmt"/><path class="puyadibwf"/><path class="djxw08b2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:images-duotone" {...props}></Icon>
