<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_t22y96m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j_t22y96m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:folder-add" {...props}></Icon>
