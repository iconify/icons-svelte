<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovevfhr9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ovevfhr9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:antenna-bars-filled" {...props}></Icon>
