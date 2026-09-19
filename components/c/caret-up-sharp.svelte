<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aykxs61ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aykxs61ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:caret-up-sharp" {...props}></Icon>
