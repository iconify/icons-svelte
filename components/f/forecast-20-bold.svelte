<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aezfh675b.css';
import '../../css/d/d-_30k0so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aezfh675b"/><path class="d-_30k0so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forecast-20-bold" {...props}></Icon>
