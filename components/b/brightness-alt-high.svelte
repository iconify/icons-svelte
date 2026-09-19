<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x59z4hb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x59z4hb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:brightness-alt-high" {...props}></Icon>
