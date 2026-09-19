<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq-kzfbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tq-kzfbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:pinned-dirty" {...props}></Icon>
