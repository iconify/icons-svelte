<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abeqkibnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="abeqkibnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folder-open-stroke-20" {...props}></Icon>
