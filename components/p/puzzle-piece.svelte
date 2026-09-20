<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7gqk8bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m7gqk8bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:puzzle-piece" {...props}></Icon>
