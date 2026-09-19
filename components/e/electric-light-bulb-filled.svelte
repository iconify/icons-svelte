<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gek8pcbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gek8pcbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:electric-light-bulb-filled" {...props}></Icon>
