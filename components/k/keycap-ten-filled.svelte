<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhyzjr1yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bhyzjr1yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-ten-filled" {...props}></Icon>
