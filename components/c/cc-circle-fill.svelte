<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4p9qeb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l4p9qeb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cc-circle-fill" {...props}></Icon>
