<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw9rritcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw9rritcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-text-tick" {...props}></Icon>
