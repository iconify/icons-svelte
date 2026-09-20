<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je17il--x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="je17il--x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:confectionery-15" {...props}></Icon>
