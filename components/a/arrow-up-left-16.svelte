<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ng7ob0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9ng7ob0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-up-left-16" {...props}></Icon>
