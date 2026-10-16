<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu57r0fpa.css';
import '../../css/b/by5oxcb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iu57r0fpa"/><path class="by5oxcb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reactor-48-bold" {...props}></Icon>
