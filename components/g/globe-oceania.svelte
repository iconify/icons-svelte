<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st8g0vigt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="st8g0vigt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:globe-oceania" {...props}></Icon>
