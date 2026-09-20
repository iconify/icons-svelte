<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r19nw1ghx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r19nw1ghx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:asterisk" {...props}></Icon>
