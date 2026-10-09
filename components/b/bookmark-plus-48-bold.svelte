<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ue9wb8n.css';
import '../../css/r/re6y0hbtf.css';
import '../../css/j/jfdfjcbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b7ue9wb8n"/><path class="re6y0hbtf"/><path class="jfdfjcbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-plus-48-bold" {...props}></Icon>
