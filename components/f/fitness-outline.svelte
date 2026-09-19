<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_9aq5btt.css';
import '../../css/k/k767t9bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_9aq5btt"/><path class="k767t9bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:fitness-outline" {...props}></Icon>
