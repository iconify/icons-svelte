<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb1we2zpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rb1we2zpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-fn-filled" {...props}></Icon>
