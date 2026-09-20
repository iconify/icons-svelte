<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b48va0b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="b48va0b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:external" {...props}></Icon>
