<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzijosb1g.css';
import '../../css/h/hg3-fcc3e.css';
import '../../css/x/xbitz5bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rzijosb1g"/><path class="hg3-fcc3e"/><path class="xbitz5bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:furnace-20-bold" {...props}></Icon>
