<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2mpj1aue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r2mpj1aue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horse-under-gabled-roof" {...props}></Icon>
