<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n55ad0htp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="n55ad0htp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-point-down" {...props}></Icon>
