<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edlr2ix5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="edlr2ix5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:mail3" {...props}></Icon>
