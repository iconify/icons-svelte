<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmbneo8nu.css';
import '../../css/x/x-j_oib3m.css';
import '../../css/e/ef10pob7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fmbneo8nu"/><path class="x-j_oib3m"/><path class="ef10pob7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-elbow-20-bold" {...props}></Icon>
