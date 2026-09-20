<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg-731b9u.css';
import '../../css/p/pxacudx8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fg-731b9u"/><path class="pxacudx8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:phonecall-solid" {...props}></Icon>
