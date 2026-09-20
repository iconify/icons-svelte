<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo-b3efua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo-b3efua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-transfer-fill" {...props}></Icon>
