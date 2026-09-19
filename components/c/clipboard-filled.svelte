<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv-y-4o-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hv-y-4o-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:clipboard-filled" {...props}></Icon>
