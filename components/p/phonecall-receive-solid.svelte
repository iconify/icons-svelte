<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxacudx8p.css';
import '../../css/s/s4p2gkl9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pxacudx8p"/><path class="s4p2gkl9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:phonecall-receive-solid" {...props}></Icon>
