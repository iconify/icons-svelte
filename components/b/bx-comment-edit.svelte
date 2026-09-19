<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lob1607iw.css';
import '../../css/j/j1kdqfrps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lob1607iw"/><path class="j1kdqfrps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-comment-edit" {...props}></Icon>
