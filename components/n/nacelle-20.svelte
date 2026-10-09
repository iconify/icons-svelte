<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjzhse32s.css';
import '../../css/y/y-a7xo-fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mjzhse32s"/><path class="y-a7xo-fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nacelle-20" {...props}></Icon>
