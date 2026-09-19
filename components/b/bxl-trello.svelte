<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obliqlb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obliqlb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-trello" {...props}></Icon>
