<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf-8-3bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jf-8-3bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:folder-open" {...props}></Icon>
