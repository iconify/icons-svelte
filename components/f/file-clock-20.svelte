<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp9jrqb6k.css';
import '../../css/e/efx3s8brg.css';
import '../../css/k/kf8qud5kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hp9jrqb6k"/><path class="efx3s8brg"/><path class="kf8qud5kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-clock-20" {...props}></Icon>
