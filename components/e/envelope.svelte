<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxr5i9bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rxr5i9bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:envelope" {...props}></Icon>
