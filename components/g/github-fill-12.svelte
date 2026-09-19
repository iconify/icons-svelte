<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jves9ubuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jves9ubuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:github-fill-12" {...props}></Icon>
