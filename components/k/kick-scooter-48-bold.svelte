<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h72dw-q8s.css';
import '../../css/a/az0wvsxpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h72dw-q8s"/><path class="az0wvsxpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kick-scooter-48-bold" {...props}></Icon>
