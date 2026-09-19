<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekz8ovone.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ekz8ovone"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:hexagon" {...props}></Icon>
