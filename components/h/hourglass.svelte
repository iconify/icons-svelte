<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvpw1ac4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="mvpw1ac4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hourglass" {...props}></Icon>
