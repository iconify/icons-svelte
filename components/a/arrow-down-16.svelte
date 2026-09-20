<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klr151b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="klr151b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-down-16" {...props}></Icon>
