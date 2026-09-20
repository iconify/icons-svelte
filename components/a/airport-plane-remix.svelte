<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi21tmbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xi21tmbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airport-plane-remix" {...props}></Icon>
