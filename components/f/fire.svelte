<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7ns8abmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="o7ns8abmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:fire" {...props}></Icon>
