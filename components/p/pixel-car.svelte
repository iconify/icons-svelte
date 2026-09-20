<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9v_h1fdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c9v_h1fdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-car" {...props}></Icon>
