<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knx2mmctr.css';
import '../../css/g/g8p6evbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="knx2mmctr"/><path class="g8p6evbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:deforestation-20" {...props}></Icon>
