<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5gnv6y7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n5gnv6y7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:issue-draft" {...props}></Icon>
