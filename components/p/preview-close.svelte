<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1dlbhb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h1dlbhb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:preview-close" {...props}></Icon>
