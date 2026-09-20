<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx2mo8b7f.css';
import '../../css/b/bc7209bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vx2mo8b7f"/><path class="bc7209bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:boson" {...props}></Icon>
