<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2auq2b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="b2auq2b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:golf-11" {...props}></Icon>
