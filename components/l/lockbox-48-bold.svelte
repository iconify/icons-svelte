<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlhsvkb_y.css';
import '../../css/p/pkf1_sbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hlhsvkb_y"/><path class="pkf1_sbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lockbox-48-bold" {...props}></Icon>
