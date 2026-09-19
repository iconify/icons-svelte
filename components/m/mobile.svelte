<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soev48dsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="soev48dsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:mobile" {...props}></Icon>
