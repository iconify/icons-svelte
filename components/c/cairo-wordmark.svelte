<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-hqinbet.css';
import '../../css/x/xs145wb_x.css';
import '../../css/k/k3j1totiu.css';
import '../../css/w/w32au1bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a-hqinbet"/><path class="xs145wb_x"/><path class="k3j1totiu"/><path class="w32au1bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cairo-wordmark" {...props}></Icon>
