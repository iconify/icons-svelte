<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alazuk46f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="alazuk46f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish1-neutral" {...props}></Icon>
