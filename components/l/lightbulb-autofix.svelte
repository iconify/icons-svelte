<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vumcn1b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vumcn1b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:lightbulb-autofix" {...props}></Icon>
