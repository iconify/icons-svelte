<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bitppkb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bitppkb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:archive-drawer-fill" {...props}></Icon>
