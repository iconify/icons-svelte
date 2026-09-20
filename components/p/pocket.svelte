<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzm6tn2ba.css';
import '../../css/f/fyf-67bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14.464,"height":12.504};
const content = `<path clip-rule="evenodd" class="pzm6tn2ba"/><path class="fyf-67bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pocket" {...props}></Icon>
