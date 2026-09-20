<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e869w8bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e869w8bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-push-16" {...props}></Icon>
