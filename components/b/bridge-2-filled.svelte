<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e35l8w-da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e35l8w-da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bridge-2-filled" {...props}></Icon>
