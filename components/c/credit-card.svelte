<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6semq9-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b6semq9-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:credit-card" {...props}></Icon>
