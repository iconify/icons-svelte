<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7p34wbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="q7p34wbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:linkedin" {...props}></Icon>
