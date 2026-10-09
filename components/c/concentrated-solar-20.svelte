<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtsgfacfk.css';
import '../../css/b/bzc7trb_y.css';
import '../../css/n/nwz76kjzw.css';
import '../../css/h/hztb-052z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wtsgfacfk"/><path class="bzc7trb_y"/><path class="nwz76kjzw"/><path class="hztb-052z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:concentrated-solar-20" {...props}></Icon>
