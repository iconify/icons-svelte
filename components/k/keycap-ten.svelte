<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmpyr-udc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jmpyr-udc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-ten" {...props}></Icon>
