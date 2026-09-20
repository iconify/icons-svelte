<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l32lerbfx.css';
import '../../css/o/opwjgvbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l32lerbfx"/><path class="opwjgvbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-cline-open" {...props}></Icon>
