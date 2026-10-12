<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-li_8-0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x-li_8-0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pause-stroke-20" {...props}></Icon>
