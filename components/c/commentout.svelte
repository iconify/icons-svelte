<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkauw5mui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bkauw5mui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:commentout" {...props}></Icon>
