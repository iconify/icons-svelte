<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f02hbyofe.css';
import '../../css/b/bm8h3db9m.css';
import '../../css/d/ddmfo5g7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f02hbyofe"/><path class="bm8h3db9m"/><path class="ddmfo5g7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:luau-test" {...props}></Icon>
