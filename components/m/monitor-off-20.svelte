<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7x5yta8s.css';
import '../../css/k/kvl9ucc0s.css';
import '../../css/p/pssx0khhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l7x5yta8s"/><path class="kvl9ucc0s"/><path class="pssx0khhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-off-20" {...props}></Icon>
