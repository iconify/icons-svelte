<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuveebb1b.css';
import '../../css/z/ziroa4b5h.css';
import '../../css/b/b3g5khbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zuveebb1b"/><path class="ziroa4b5h"/><path class="b3g5khbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-alert-20-bold" {...props}></Icon>
