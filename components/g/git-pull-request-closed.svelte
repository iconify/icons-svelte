<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucdhvsbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ucdhvsbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-pull-request-closed" {...props}></Icon>
