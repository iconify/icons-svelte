<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbu-t6btd.css';
import '../../css/w/wou0m8doy.css';
import '../../css/j/jaje2urvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kbu-t6btd"/><path class="wou0m8doy"/><path class="jaje2urvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-square-48-bold" {...props}></Icon>
