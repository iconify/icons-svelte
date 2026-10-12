<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxzfl5btn.css';
import '../../css/e/ekw862bgh.css';
import '../../css/d/d8p7d1b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lxzfl5btn"/><path class="ekw862bgh"/><path class="d8p7d1b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paste-48" {...props}></Icon>
