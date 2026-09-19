<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eibzgdcne.css';
import '../../css/m/mhb2ho-ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="eibzgdcne"/><path class="mhb2ho-ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:right" {...props}></Icon>
