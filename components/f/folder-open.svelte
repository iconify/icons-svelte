<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgg-w0bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgg-w0bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:folder-open" {...props}></Icon>
