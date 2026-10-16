<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k86i3-bfg.css';
import '../../css/s/sggm0biti.css';
import '../../css/n/nq52osbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k86i3-bfg"/><path class="sggm0biti"/><path class="nq52osbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-input-20-bold" {...props}></Icon>
