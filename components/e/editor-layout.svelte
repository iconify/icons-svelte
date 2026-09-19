<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk2e3lkou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pk2e3lkou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:editor-layout" {...props}></Icon>
