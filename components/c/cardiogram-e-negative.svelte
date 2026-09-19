<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/upt6vgbkc.css';
import '../../css/n/n8yd7w-5u.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsCardiogramENegative0)" class="cuyn6tgcc"><path class="upt6vgbkc"/><path clip-rule="evenodd" class="n8yd7w-5u"/></g><defs><clipPath id="healthiconsCardiogramENegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cardiogram-e-negative" {...props}></Icon>
