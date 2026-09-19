<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gknle0bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gknle0bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:electric-light-bulb-small" {...props}></Icon>
