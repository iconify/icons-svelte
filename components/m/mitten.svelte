<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2co7ri_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w2co7ri_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mitten" {...props}></Icon>
