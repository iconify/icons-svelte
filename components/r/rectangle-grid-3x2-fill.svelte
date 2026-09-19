<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0a7ymb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="z0a7ymb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-grid-3x2-fill" {...props}></Icon>
