<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8d2m-gls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f8d2m-gls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:door-open-fill" {...props}></Icon>
