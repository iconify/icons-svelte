<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9jx6gj_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z9jx6gj_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:latin-cross-on-square" {...props}></Icon>
