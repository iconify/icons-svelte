<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_k1aixrm.css';
import '../../css/q/qrzlcfwkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k_k1aixrm"/><path clip-rule="evenodd" class="qrzlcfwkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-dpad-16" {...props}></Icon>
