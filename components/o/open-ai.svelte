<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm_om44gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="bm_om44gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:open-ai" {...props}></Icon>
