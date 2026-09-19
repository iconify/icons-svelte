<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8iepnbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8iepnbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-empty-01" {...props}></Icon>
