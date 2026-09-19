<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmwxaignu.css';
import '../../css/u/u86eo8b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zmwxaignu"/><path class="u86eo8b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-center" {...props}></Icon>
