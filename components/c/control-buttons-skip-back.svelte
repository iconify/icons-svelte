<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd35uf49z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rd35uf49z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-skip-back" {...props}></Icon>
