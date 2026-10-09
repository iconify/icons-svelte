<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6cvwtbsp.css';
import '../../css/n/nw87p9b0z.css';
import '../../css/j/j9-dsob8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d6cvwtbsp"/><path class="nw87p9b0z"/><path class="j9-dsob8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:canal-lock-48-bold" {...props}></Icon>
