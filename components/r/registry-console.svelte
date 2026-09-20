<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc17ftbpa.css';
import '../../css/c/c2ggwgpcw.css';
import '../../css/l/l6tftisdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jc17ftbpa"/><path class="c2ggwgpcw"/><path class="l6tftisdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:registry-console" {...props}></Icon>
