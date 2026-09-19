<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9kqm51ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":488,"height":496};
const content = `<path class="b9kqm51ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:brightness-5" {...props}></Icon>
