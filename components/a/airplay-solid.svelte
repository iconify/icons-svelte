<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krf7npbdz.css';
import '../../css/m/m3scqya2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="krf7npbdz"/><path class="m3scqya2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:airplay-solid" {...props}></Icon>
