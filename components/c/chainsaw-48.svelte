<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tht13fb0t.css';
import '../../css/d/d9xo1bc7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tht13fb0t"/><path class="d9xo1bc7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chainsaw-48" {...props}></Icon>
