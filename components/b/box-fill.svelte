<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi29nzmav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xi29nzmav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box-fill" {...props}></Icon>
