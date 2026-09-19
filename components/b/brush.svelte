<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy9_-jbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="xy9_-jbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:brush" {...props}></Icon>
