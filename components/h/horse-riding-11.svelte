<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_ivvacuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="h_ivvacuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:horse-riding-11" {...props}></Icon>
