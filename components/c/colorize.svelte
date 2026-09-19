<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6nhtqbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="r6nhtqbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:colorize" {...props}></Icon>
