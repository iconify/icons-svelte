<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1m-6qb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t1m-6qb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:door-closed-solid" {...props}></Icon>
