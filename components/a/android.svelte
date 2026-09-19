<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2_trcbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="u2_trcbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:android" {...props}></Icon>
