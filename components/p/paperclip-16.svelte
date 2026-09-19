<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvunr3b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lvunr3b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:paperclip-16" {...props}></Icon>
