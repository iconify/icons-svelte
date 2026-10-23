<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm5h1yb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5h1yb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:kanban" {...props}></Icon>
