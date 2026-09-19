<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjlsuub8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yjlsuub8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chevron-down-compact" {...props}></Icon>
