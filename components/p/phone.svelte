<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lok_wbboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lok_wbboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:phone" {...props}></Icon>
