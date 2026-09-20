<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwh9o9uom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cwh9o9uom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:lock" {...props}></Icon>
