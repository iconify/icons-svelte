<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj8r7vbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fj8r7vbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-waiters-attire-holding-tray-with-wine-glass" {...props}></Icon>
