<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8t72pbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h8t72pbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:circle-slash-compact" {...props}></Icon>
