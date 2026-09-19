<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dck7173le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dck7173le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:folder-delete" {...props}></Icon>
