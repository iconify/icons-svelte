<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf3wb_zhv.css';
import '../../css/x/xbbrjje4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nf3wb_zhv"/><path class="xbbrjje4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clapperboard-20" {...props}></Icon>
