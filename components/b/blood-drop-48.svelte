<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsu7h-b-q.css';
import '../../css/s/sn3j5vz1q.css';
import '../../css/c/c4_zttl1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fsu7h-b-q"/><path class="sn3j5vz1q"/><path class="c4_zttl1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blood-drop-48" {...props}></Icon>
