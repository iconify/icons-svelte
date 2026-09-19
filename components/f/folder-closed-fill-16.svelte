<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v58lonbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v58lonbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folder-closed-fill-16" {...props}></Icon>
