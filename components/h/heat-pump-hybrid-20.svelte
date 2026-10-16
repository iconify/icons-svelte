<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt8maz9hk.css';
import '../../css/f/f2c2p1hyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vt8maz9hk"/><path class="f2c2p1hyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-hybrid-20" {...props}></Icon>
