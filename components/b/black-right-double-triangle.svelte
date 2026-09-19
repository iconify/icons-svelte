<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z02_g1b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z02_g1b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-right-double-triangle" {...props}></Icon>
