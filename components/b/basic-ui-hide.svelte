<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpy9h52dg.css';
import '../../css/b/b9rr1pb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hpy9h52dg"/><path class="b9rr1pb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-hide" {...props}></Icon>
