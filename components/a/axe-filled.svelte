<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik3bbzb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ik3bbzb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:axe-filled" {...props}></Icon>
