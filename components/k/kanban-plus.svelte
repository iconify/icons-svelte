<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcvw__bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcvw__bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:kanban-plus" {...props}></Icon>
