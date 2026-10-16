<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afybf8_hq.css';
import '../../css/n/naopco_rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="afybf8_hq"/><path class="naopco_rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:core-sample-20-bold" {...props}></Icon>
