<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyjx8ab4r.css';
import '../../css/e/e2y089rqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cyjx8ab4r"/><path class="e2y089rqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hair-dryer-48" {...props}></Icon>
