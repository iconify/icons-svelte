<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4hvibczh.css';
import '../../css/p/p-3uqobhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4hvibczh"/><path class="p-3uqobhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bookmarks" {...props}></Icon>
