<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5hh3ac5g.css';
import '../../css/q/q761jsrye.css';
import '../../css/g/gpknbotbu.css';
import '../../css/c/ceg2-nwwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m5hh3ac5g"/><path class="q761jsrye"/><path class="gpknbotbu"/><path class="ceg2-nwwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-recycle-20" {...props}></Icon>
