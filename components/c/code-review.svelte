<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3z2p1b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z3z2p1b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:code-review" {...props}></Icon>
