<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f53z1qbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f53z1qbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:home-fill-12" {...props}></Icon>
