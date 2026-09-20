<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/makww4bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="makww4bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:kanban" {...props}></Icon>
