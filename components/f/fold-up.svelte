<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrav0nbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mrav0nbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fold-up" {...props}></Icon>
