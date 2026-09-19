<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp1re3c8g.css';
import '../../css/g/gdtbnxj2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fp1re3c8g"/><path class="gdtbnxj2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:copy" {...props}></Icon>
