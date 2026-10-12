<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuj2oe5ct.css';
import '../../css/s/sf2s86-6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xuj2oe5ct"/><path class="sf2s86-6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:luggage-48" {...props}></Icon>
