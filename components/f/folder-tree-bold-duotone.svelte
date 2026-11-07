<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn8j1cc6q.css';
import '../../css/b/by22ydp5s.css';
import '../../css/q/quxmn86ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn8j1cc6q"/><path class="by22ydp5s"/><path class="quxmn86ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-tree-bold-duotone" {...props}></Icon>
