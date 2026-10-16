<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqsl-cq4l.css';
import '../../css/r/rzc5_66zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mqsl-cq4l"/><path class="rzc5_66zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:and-gate-48" {...props}></Icon>
