<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fgu4rmb1d.css';
import '../../css/h/hupmt3b1b.css';
import '../../css/l/l5ipexjai.css';
import '../../css/o/o4feiio3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fgu4rmb1d"/><path class="hupmt3b1b"/><path class="l5ipexjai"/><path class="o4feiio3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rabbit-duotone" {...props}></Icon>
