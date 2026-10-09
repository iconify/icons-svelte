<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmgp-hp4m.css';
import '../../css/b/b0-65lw1h.css';
import '../../css/w/weuhzbcsv.css';
import '../../css/j/jbjwaubeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rmgp-hp4m"/><path class="b0-65lw1h"/><path class="weuhzbcsv"/><path class="jbjwaubeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-key-20-bold" {...props}></Icon>
