<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1my9l8uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1my9l8uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dodging" {...props}></Icon>
