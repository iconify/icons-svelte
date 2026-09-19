<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6jsscczo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":456};
const content = `<path class="k6jsscczo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flash-auto" {...props}></Icon>
