<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km2fl-ght.css';
import '../../css/g/gjj2m4rmf.css';
import '../../css/u/ut1x-4bwy.css';
import '../../css/l/l5mv3femf.css';
import '../../css/a/aw2ifkfec.css';
import '../../css/d/dw57tibvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="km2fl-ght"/><path class="gjj2m4rmf"/><path class="ut1x-4bwy"/><path class="l5mv3femf"/><path class="aw2ifkfec"/><path class="dw57tibvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-box-plot-20" {...props}></Icon>
