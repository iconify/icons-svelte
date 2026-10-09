<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df7n374tg.css';
import '../../css/a/aouq01bvp.css';
import '../../css/m/mzeei2eeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="df7n374tg"/><path class="aouq01bvp"/><path class="mzeei2eeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:certificate-20-bold" {...props}></Icon>
