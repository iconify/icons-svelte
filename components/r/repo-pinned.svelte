<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fif97fbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fif97fbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:repo-pinned" {...props}></Icon>
