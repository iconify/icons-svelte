<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vefu94b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="vefu94b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mars-stroke-v" {...props}></Icon>
