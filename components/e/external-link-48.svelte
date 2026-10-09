<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7tl3x9ws.css';
import '../../css/b/bbz-6ubma.css';
import '../../css/l/lj5rvulqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l7tl3x9ws"/><path class="bbz-6ubma"/><path class="lj5rvulqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:external-link-48" {...props}></Icon>
