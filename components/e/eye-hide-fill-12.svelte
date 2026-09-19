<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lksl6vb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lksl6vb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eye-hide-fill-12" {...props}></Icon>
