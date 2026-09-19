<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghu6qbdwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ghu6qbdwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pushpin-filled" {...props}></Icon>
