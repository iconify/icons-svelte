<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcv3k0ieq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lcv3k0ieq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:pagoda" {...props}></Icon>
