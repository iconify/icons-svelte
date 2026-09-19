<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j26jo9bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j26jo9bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-pull-request" {...props}></Icon>
