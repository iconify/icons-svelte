<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvhu42n8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvhu42n8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-check-fill" {...props}></Icon>
