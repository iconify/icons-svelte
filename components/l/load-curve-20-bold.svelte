<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aezfh675b.css';
import '../../css/p/p7d-fccgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aezfh675b"/><path class="p7d-fccgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:load-curve-20-bold" {...props}></Icon>
