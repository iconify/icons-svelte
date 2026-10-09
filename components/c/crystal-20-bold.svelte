<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay_tk8c1e.css';
import '../../css/l/lg77w-bbs.css';
import '../../css/a/aq913o2sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ay_tk8c1e"/><path class="lg77w-bbs"/><path class="aq913o2sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crystal-20-bold" {...props}></Icon>
