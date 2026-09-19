<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxk-lf9th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="vxk-lf9th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:quidditch" {...props}></Icon>
