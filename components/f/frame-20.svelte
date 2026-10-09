<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njicu-b5r.css';
import '../../css/i/i2ndmodxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="njicu-b5r"/><path class="i2ndmodxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frame-20" {...props}></Icon>
