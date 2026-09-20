<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq736qbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rq736qbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:redo" {...props}></Icon>
