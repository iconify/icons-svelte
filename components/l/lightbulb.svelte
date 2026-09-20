<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4oyap5nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d4oyap5nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:lightbulb" {...props}></Icon>
