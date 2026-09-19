<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thui0ru5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thui0ru5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fold-down" {...props}></Icon>
