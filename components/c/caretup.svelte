<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfvwfdc9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":9};
const content = `<path class="vfvwfdc9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:caretup" {...props}></Icon>
