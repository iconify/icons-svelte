<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exh-jfbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="exh-jfbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:book-compact" {...props}></Icon>
