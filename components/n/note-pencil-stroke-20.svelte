<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs40jpbkq.css';
import '../../css/r/r5w09bcrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rs40jpbkq"/><path class="r5w09bcrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:note-pencil-stroke-20" {...props}></Icon>
