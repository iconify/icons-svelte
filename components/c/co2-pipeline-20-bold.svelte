<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udeabbl7f.css';
import '../../css/b/b82thot2p.css';
import '../../css/f/fkr7gxrju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="udeabbl7f"/><path class="b82thot2p"/><path class="fkr7gxrju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-pipeline-20-bold" {...props}></Icon>
