<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjbpxbblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjbpxbblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-x" {...props}></Icon>
