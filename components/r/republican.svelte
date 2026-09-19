<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9yrrwb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="a9yrrwb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:republican" {...props}></Icon>
