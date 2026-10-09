<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1x-ibbak.css';
import '../../css/h/hlue_gbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v1x-ibbak"/><path class="hlue_gbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pellet-boiler-20-bold" {...props}></Icon>
