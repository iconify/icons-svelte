<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilf28rb4r.css';
import '../../css/r/rilm8wbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ilf28rb4r"/><path class="rilm8wbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flame-20" {...props}></Icon>
