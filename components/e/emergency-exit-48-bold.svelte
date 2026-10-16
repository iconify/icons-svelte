<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9e0p_b-j.css';
import '../../css/b/b34wfpb4d.css';
import '../../css/e/eg_6x1bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9e0p_b-j"/><path class="b34wfpb4d"/><path class="eg_6x1bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emergency-exit-48-bold" {...props}></Icon>
