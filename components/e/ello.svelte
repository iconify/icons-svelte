<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbfsm8byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hbfsm8byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:ello" {...props}></Icon>
