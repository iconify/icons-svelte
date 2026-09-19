<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d70qsmb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d70qsmb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-down" {...props}></Icon>
