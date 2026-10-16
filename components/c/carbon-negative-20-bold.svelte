<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4n2q8cza.css';
import '../../css/k/kehgtcamx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h4n2q8cza"/><path class="kehgtcamx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-negative-20-bold" {...props}></Icon>
