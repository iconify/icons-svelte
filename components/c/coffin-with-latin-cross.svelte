<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h05wg1b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h05wg1b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-latin-cross" {...props}></Icon>
