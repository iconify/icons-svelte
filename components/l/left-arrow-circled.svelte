<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2btll5sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m2btll5sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-arrow-circled" {...props}></Icon>
