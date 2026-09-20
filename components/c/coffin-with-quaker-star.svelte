<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4v7wtbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y4v7wtbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-quaker-star" {...props}></Icon>
