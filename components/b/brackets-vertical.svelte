<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zojfblbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zojfblbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:brackets-vertical" {...props}></Icon>
