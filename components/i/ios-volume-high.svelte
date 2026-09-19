<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tej_g1b-d.css';
import '../../css/n/nwq7urbqo.css';
import '../../css/t/twswkdbiy.css';
import '../../css/p/p7wko903m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tej_g1b-d"/><path class="nwq7urbqo"/><path class="twswkdbiy"/><path class="p7wko903m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-volume-high" {...props}></Icon>
