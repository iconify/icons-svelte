<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoj0_sxob.css';
import '../../css/v/voqlvbrhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eoj0_sxob"/><path class="voqlvbrhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-closed-16" {...props}></Icon>
