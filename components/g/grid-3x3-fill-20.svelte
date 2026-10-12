<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlvd9ykgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mlvd9ykgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-3x3-fill-20" {...props}></Icon>
