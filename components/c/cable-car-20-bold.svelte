<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy6sxlqhk.css';
import '../../css/b/bxahjo3ap.css';
import '../../css/y/ycnogikcx.css';
import '../../css/j/j37rrvywc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qy6sxlqhk"/><path class="bxahjo3ap"/><path class="ycnogikcx"/><path class="j37rrvywc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-car-20-bold" {...props}></Icon>
