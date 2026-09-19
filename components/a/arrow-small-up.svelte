<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk9_gubeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rk9_gubeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-small-up" {...props}></Icon>
