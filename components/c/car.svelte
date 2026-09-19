<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bopws0e3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bopws0e3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:car" {...props}></Icon>
