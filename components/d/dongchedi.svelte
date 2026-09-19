<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1v12nz2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j1v12nz2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dongchedi" {...props}></Icon>
