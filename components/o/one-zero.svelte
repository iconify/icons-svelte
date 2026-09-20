<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmxbay76f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tmxbay76f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:one-zero" {...props}></Icon>
