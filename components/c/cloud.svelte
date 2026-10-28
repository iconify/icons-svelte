<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrw5sjivn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw5sjivn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:cloud" {...props}></Icon>
