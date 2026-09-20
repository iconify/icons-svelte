<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lztc1r74z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="lztc1r74z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:grab" {...props}></Icon>
