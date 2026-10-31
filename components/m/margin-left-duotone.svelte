<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/ft9nhnbbu.css';
import '../../css/p/ph1021bnv.css';
import '../../css/z/zh-iwu6pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ft9nhnbbu"/><path class="ph1021bnv"/><path class="zh-iwu6pi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:margin-left-duotone" {...props}></Icon>
