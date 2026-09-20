<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uktee8nma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uktee8nma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remove-folder-outline" {...props}></Icon>
