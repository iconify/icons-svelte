<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/khmt06b9h.css';
import '../../css/l/lrnov0b9n.css';
import '../../css/o/o7k4dccfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="khmt06b9h"/><path class="lrnov0b9n"/><path class="o7k4dccfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:muscle" {...props}></Icon>
