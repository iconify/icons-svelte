<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fce7lrm6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fce7lrm6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:flower2" {...props}></Icon>
