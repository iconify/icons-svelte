<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly39wyb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ly39wyb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:neos" {...props}></Icon>
