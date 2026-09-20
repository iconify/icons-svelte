<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdr707jxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cdr707jxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-hand-move" {...props}></Icon>
