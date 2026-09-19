<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbecdteru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tbecdteru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-medkit" {...props}></Icon>
