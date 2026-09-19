<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rktcl5r9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rktcl5r9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:diff-ignored" {...props}></Icon>
