<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci5wxgb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ci5wxgb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:repo-forked-compact" {...props}></Icon>
