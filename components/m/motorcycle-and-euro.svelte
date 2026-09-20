<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el96rjbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="el96rjbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-and-euro" {...props}></Icon>
