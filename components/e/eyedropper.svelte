<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izh_9ib_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="izh_9ib_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:eyedropper" {...props}></Icon>
