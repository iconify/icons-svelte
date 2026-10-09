<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc7b7e4ab.css';
import '../../css/u/un07r_bjv.css';
import '../../css/p/pdn0d5lux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bc7b7e4ab"/><path class="un07r_bjv"/><path class="pdn0d5lux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lpg-tank-48-bold" {...props}></Icon>
