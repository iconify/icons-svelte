<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0ul-uz9o.css';
import '../../css/o/oc7c-mb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0ul-uz9o"/><path class="oc7c-mb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:alarm" {...props}></Icon>
