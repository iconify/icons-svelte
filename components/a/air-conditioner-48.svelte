<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpi6w4uli.css';
import '../../css/l/llqv7ablr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xpi6w4uli"/><path class="llqv7ablr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-conditioner-48" {...props}></Icon>
