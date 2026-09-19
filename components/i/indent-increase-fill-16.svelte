<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efihxg8fx.css';
import '../../css/s/sz9hlnbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="efihxg8fx"/><path class="sz9hlnbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:indent-increase-fill-16" {...props}></Icon>
