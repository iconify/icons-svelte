<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5-mp9b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="i5-mp9b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:meh-o" {...props}></Icon>
