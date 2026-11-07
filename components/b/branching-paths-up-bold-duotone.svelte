<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd39qiwhy.css';
import '../../css/m/mn-eum1fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd39qiwhy"/><path class="mn-eum1fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:branching-paths-up-bold-duotone" {...props}></Icon>
