<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdltw8kvl.css';
import '../../css/x/x-t9vyu4u.css';
import '../../css/m/mdhfcqbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rdltw8kvl"/><path class="x-t9vyu4u"/><path class="mdhfcqbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blade-pitch-48-bold" {...props}></Icon>
