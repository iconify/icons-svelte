<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbcnw6b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gbcnw6b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle-pause" {...props}></Icon>
