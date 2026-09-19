<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6g6t1bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e6g6t1bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:hourglass" {...props}></Icon>
