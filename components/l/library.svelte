<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq4awzbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="rq4awzbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:library" {...props}></Icon>
