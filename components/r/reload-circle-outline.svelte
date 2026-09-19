<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg5j7ibl.css';
import '../../css/s/szifr4b9l.css';
import '../../css/u/un755_b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="szifr4b9l"/><path class="un755_b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:reload-circle-outline" {...props}></Icon>
