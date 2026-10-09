<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tby_lo-nb.css';
import '../../css/e/e33pt4b0g.css';
import '../../css/p/ps6ai49ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tby_lo-nb"/><path class="e33pt4b0g"/><path class="ps6ai49ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gauge-20" {...props}></Icon>
