<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1ri_k4mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c1ri_k4mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aria2-light" {...props}></Icon>
