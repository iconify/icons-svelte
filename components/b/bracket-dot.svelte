<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abo0go4gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="abo0go4gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:bracket-dot" {...props}></Icon>
