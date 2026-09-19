<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ku2cciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o1ku2cciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:decrease-indent-text-mirrored" {...props}></Icon>
