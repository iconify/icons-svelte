<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy7r9nb-t.css';
import '../../css/g/gfq35jb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy7r9nb-t"/><path class="gfq35jb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-favourite-bookmark-bold" {...props}></Icon>
