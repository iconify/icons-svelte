<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_-xvvo4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224,"height":80,"left":36,"top":112};
const content = `<path class="l_-xvvo4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mir" {...props}></Icon>
