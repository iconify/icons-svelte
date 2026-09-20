<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds199pbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ds199pbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-top-right" {...props}></Icon>
