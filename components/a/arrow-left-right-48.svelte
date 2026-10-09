<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5yx1ibtg.css';
import '../../css/f/fostv5aqj.css';
import '../../css/d/dg_f4ibgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p5yx1ibtg"/><path class="fostv5aqj"/><path class="dg_f4ibgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-right-48" {...props}></Icon>
