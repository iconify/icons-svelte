<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0y0atbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="h0y0atbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:certificate" {...props}></Icon>
