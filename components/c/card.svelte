<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc9bi-5wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hc9bi-5wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:card" {...props}></Icon>
