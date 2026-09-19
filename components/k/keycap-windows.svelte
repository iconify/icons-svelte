<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm2z31b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rm2z31b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-windows" {...props}></Icon>
