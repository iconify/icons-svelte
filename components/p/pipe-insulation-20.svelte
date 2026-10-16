<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz02lvbot.css';
import '../../css/z/z7r22xbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lz02lvbot"/><path class="z7r22xbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-insulation-20" {...props}></Icon>
