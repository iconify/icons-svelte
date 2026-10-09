<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m091oxbzr.css';
import '../../css/p/p-bs16b4r.css';
import '../../css/t/tzmu4f8me.css';
import '../../css/q/qfmb5ts5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m091oxbzr"/><path class="p-bs16b4r"/><path class="tzmu4f8me"/><path class="qfmb5ts5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:motorcycle-48-bold" {...props}></Icon>
