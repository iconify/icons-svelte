<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juznr5scs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="juznr5scs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:folder-exclamation" {...props}></Icon>
