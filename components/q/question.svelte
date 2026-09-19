<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ihd2q809h.css';
import '../../css/o/olg0x-m0f.css';
import '../../css/s/sovlp1b4o.css';
import '../../css/f/fv0al6bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ihd2q809h"/><path clip-rule="evenodd" class="olg0x-m0f"/><path clip-rule="evenodd" class="sovlp1b4o"/><path clip-rule="evenodd" class="fv0al6bdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:question" {...props}></Icon>
