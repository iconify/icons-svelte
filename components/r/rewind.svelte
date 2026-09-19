<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bug2scxnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bug2scxnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:rewind" {...props}></Icon>
