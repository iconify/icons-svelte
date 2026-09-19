<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yws0--ucd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yws0--ucd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:h5" {...props}></Icon>
