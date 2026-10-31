<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvmk2esxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tvmk2esxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-gabled-building-with-fireplace-and-chimney" {...props}></Icon>
