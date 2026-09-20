<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9q7t8bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9q7t8bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-to-folder-outline" {...props}></Icon>
