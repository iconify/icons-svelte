<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqsd-vb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rqsd-vb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:netease-music" {...props}></Icon>
