<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w07i9qbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w07i9qbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rectangle-shape-solid" {...props}></Icon>
