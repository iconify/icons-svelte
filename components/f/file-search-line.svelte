<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od1x1ly1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od1x1ly1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-search-line" {...props}></Icon>
