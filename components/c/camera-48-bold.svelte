<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdrt4wkoq.css';
import '../../css/i/iwhux3djk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hdrt4wkoq"/><path class="iwhux3djk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-48-bold" {...props}></Icon>
