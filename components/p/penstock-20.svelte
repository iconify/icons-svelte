<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh3xhwb0f.css';
import '../../css/g/gfokxvboe.css';
import '../../css/m/m42n8zsrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uh3xhwb0f"/><path class="gfokxvboe"/><path class="m42n8zsrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:penstock-20" {...props}></Icon>
