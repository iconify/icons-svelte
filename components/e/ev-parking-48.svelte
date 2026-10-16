<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5i9cpbbm.css';
import '../../css/k/k1a5ibk1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x5i9cpbbm"/><path class="k1a5ibk1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-parking-48" {...props}></Icon>
