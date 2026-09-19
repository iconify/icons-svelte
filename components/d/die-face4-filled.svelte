<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emu97kndw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="emu97kndw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face4-filled" {...props}></Icon>
