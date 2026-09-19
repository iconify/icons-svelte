<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8reapder.css';
import '../../css/a/ail0khy-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v8reapder"/><path class="ail0khy-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drone" {...props}></Icon>
