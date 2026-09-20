<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn9fr8b3o.css';
import '../../css/i/i8m7q71ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="jn9fr8b3o"/><path class="i8m7q71ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:consumption-o" {...props}></Icon>
