<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyi0w9b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jyi0w9b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:arrow-right" {...props}></Icon>
