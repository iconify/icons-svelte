<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ref45cb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ref45cb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:octopus" {...props}></Icon>
