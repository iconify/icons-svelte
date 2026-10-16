<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9pto6bfk.css';
import '../../css/h/hb4ovmb-c.css';
import '../../css/b/betbcgbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9pto6bfk"/><path class="hb4ovmb-c"/><path class="betbcgbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:circular-saw-48" {...props}></Icon>
