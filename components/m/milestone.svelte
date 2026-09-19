<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz9ax0bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iz9ax0bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:milestone" {...props}></Icon>
