<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m640zw-kt.css';
import '../../css/p/pvo4qd6wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m640zw-kt"/><path class="pvo4qd6wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ballottboxwithscriptx" {...props}></Icon>
