<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spw8_85nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spw8_85nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-fast-forward" {...props}></Icon>
