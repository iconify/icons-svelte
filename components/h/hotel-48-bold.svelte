<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pla65zbzp.css';
import '../../css/t/tmookwb_d.css';
import '../../css/s/sbar25bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pla65zbzp"/><path class="tmookwb_d"/><path class="sbar25bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hotel-48-bold" {...props}></Icon>
