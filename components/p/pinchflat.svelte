<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg5m1db1h.css';
import '../../css/a/a2j6mnb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":608.3,"height":608.3,"left":-17.2,"top":-28.6};
const content = `<path class="fg5m1db1h"/><path class="a2j6mnb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pinchflat" {...props}></Icon>
