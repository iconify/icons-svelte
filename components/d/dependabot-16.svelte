<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjopbq_ry.css';
import '../../css/r/rrbhc-fdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kjopbq_ry"/><path class="rrbhc-fdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dependabot-16" {...props}></Icon>
