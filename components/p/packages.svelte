<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu-0cof9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zu-0cof9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:packages" {...props}></Icon>
