<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm84y2b2v.css';
import '../../css/e/esmuzmbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":96,"height":96};
const content = `<path class="wm84y2b2v"/><path class="esmuzmbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:copilot-96" {...props}></Icon>
