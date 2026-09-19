<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svkb8dgje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="svkb8dgje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrows-down-to-line" {...props}></Icon>
