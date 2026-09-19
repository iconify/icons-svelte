<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb26qubmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nb26qubmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:calendar-xmark" {...props}></Icon>
