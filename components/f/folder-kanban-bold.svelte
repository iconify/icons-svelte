<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp2p8cbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zp2p8cbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-kanban-bold" {...props}></Icon>
