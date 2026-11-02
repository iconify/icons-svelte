<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbwzm5bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbwzm5bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-plus-line" {...props}></Icon>
