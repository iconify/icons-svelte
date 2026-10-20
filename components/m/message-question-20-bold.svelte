<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxvbik02p.css';
import '../../css/n/nhbo4cseo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wxvbik02p"/><path class="nhbo4cseo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-question-20-bold" {...props}></Icon>
