<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcayocc6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rcayocc6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bird" {...props}></Icon>
