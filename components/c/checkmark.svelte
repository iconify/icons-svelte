<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1ibq98gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f1ibq98gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:checkmark" {...props}></Icon>
