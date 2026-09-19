<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy9xnhbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yy9xnhbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:id-alt" {...props}></Icon>
