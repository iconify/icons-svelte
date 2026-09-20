<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-2s0cbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e-2s0cbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree" {...props}></Icon>
