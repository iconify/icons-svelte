<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpdks0bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bpdks0bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:picture-tile" {...props}></Icon>
