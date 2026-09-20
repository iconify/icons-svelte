<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl695ebzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zl695ebzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:resize" {...props}></Icon>
