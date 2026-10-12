<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e1yf0t_-d.css';
import '../../css/o/o6p4tpbfx.css';
import '../../css/s/sy8bl-7cu.css';
import '../../css/h/h6iu6vb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e1yf0t_-d"/><path class="o6p4tpbfx"/><path class="sy8bl-7cu"/><path class="h6iu6vb4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panda-duotone" {...props}></Icon>
