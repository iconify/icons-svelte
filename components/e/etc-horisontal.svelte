<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfvhplb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfvhplb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:etc-horisontal" {...props}></Icon>
