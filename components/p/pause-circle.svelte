<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm4-0nyfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="cm4-0nyfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pause-circle" {...props}></Icon>
