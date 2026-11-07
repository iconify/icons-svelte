<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfpn6w7ca.css';
import '../../css/c/czn8j8ltd.css';
import '../../css/j/jp3kqwdgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfpn6w7ca"/><path class="czn8j8ltd"/><path class="jp3kqwdgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-question-mark-bold-duotone" {...props}></Icon>
