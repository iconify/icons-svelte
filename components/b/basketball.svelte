<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pazc1b7ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pazc1b7ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:basketball" {...props}></Icon>
