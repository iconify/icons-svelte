<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0iut8b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0iut8b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mars-double" {...props}></Icon>
