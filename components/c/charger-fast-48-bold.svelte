<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbi78gooe.css';
import '../../css/g/guzya4pfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fbi78gooe"/><path class="guzya4pfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-fast-48-bold" {...props}></Icon>
