<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0__vbcts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0__vbcts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-01" {...props}></Icon>
