<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9kryfb_n.css';
import '../../css/e/ed5g3xh8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9kryfb_n"/><path class="ed5g3xh8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bar-chart" {...props}></Icon>
