<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq6x1vb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pq6x1vb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:medapps" {...props}></Icon>
