<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsb8gwlib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zsb8gwlib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-outdent" {...props}></Icon>
