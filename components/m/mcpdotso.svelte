<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzxi31bwu.css';
import '../../css/e/ei30q2b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzxi31bwu"/><path class="ei30q2b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mcpdotso" {...props}></Icon>
