<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3dlznb6l.css';
import '../../css/f/f8640sn0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l3dlznb6l"/><path class="f8640sn0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frying-pan-48-bold" {...props}></Icon>
