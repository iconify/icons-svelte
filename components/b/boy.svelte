<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xss0pv79m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xss0pv79m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:boy" {...props}></Icon>
