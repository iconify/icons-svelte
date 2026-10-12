<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hnbud8kdw.css';
import '../../css/o/olsqdun8e.css';
import '../../css/y/yl8pc3bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hnbud8kdw"/><path class="olsqdun8e"/><path class="yl8pc3bzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:printer-duotone" {...props}></Icon>
