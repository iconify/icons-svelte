<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsnsd8bak.css';
import '../../css/m/mce3-1bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rsnsd8bak"/><path class="mce3-1bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:poi-home-o" {...props}></Icon>
