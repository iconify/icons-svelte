<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcg0jybbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bcg0jybbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-hollow-mirrored" {...props}></Icon>
