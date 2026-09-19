<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmhddevn.css';
import '../../css/a/avi7ktl-p.css';
import '../../css/e/e_wydyb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="lgmhddevn"/><path class="avi7ktl-p"/><path class="e_wydyb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:asset-view" {...props}></Icon>
