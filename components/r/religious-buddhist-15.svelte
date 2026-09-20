<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcri1bbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rcri1bbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-buddhist-15" {...props}></Icon>
