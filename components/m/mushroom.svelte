<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed9gmnbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="ed9gmnbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mushroom" {...props}></Icon>
