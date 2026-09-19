<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiuogw8wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="iiuogw8wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:baby" {...props}></Icon>
