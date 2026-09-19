<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyht2ts8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tyht2ts8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:pulse" {...props}></Icon>
