<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gew9h3fsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gew9h3fsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-solid" {...props}></Icon>
