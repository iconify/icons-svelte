<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk0acybbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lk0acybbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:leaf-1" {...props}></Icon>
