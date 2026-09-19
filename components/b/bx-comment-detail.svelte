<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irjsvsbnf.css';
import '../../css/j/j1kdqfrps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irjsvsbnf"/><path class="j1kdqfrps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-comment-detail" {...props}></Icon>
