<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhlt4li1n.css';
import '../../css/e/e69-qmb1n.css';
import '../../css/t/t08y0ccaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bhlt4li1n"/><path class="e69-qmb1n"/><path class="t08y0ccaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fingerprint-20" {...props}></Icon>
