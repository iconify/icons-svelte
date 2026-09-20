<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cidqwgibg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cidqwgibg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:codex" {...props}></Icon>
