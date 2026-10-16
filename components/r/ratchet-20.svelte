<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw6dnvbbs.css';
import '../../css/e/e2qan-08h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hw6dnvbbs"/><path class="e2qan-08h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ratchet-20" {...props}></Icon>
