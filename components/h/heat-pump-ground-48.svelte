<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0j8550vr.css';
import '../../css/b/bxkvxsbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s0j8550vr"/><path clip-rule="evenodd" class="bxkvxsbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-ground-48" {...props}></Icon>
