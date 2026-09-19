<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr9ytkb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="hr9ytkb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:caret-down" {...props}></Icon>
