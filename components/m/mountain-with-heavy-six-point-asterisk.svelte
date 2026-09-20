<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq1tf421r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nq1tf421r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mountain-with-heavy-six-point-asterisk" {...props}></Icon>
