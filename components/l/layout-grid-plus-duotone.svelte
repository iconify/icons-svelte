<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/ha4y_4a3w.css';
import '../../css/n/nw8k2pb0z.css';
import '../../css/o/o8yptmbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ha4y_4a3w"/><path class="nw8k2pb0z"/><path class="o8yptmbjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layout-grid-plus-duotone" {...props}></Icon>
