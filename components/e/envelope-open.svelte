<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btucvr20i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="btucvr20i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:envelope-open" {...props}></Icon>
