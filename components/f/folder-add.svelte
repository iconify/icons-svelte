<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxng2-aly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bxng2-aly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:folder-add" {...props}></Icon>
