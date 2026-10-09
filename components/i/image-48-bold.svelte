<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcfuqov3g.css';
import '../../css/m/mdy5cy31n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gcfuqov3g"/><path class="mdy5cy31n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-48-bold" {...props}></Icon>
