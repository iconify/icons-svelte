<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8xr0sedz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="b8xr0sedz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bolt" {...props}></Icon>
