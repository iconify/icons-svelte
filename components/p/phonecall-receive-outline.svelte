<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr1bbeb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cr1bbeb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:phonecall-receive-outline" {...props}></Icon>
