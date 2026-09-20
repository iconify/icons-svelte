<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqluvcqla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eqluvcqla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:breather" {...props}></Icon>
