<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_175rrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1_175rrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hotdog" {...props}></Icon>
