<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3oc6nbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j3oc6nbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:book-solid" {...props}></Icon>
