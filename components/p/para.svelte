<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t--a6rbsb.css';
import '../../css/r/r1oc-kbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t--a6rbsb"/><path class="r1oc-kbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:para" {...props}></Icon>
