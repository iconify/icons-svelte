<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boij_7x6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="boij_7x6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rectangle-tall" {...props}></Icon>
