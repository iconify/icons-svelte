<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3p-x7bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="a3p-x7bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-bold" {...props}></Icon>
