<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c61g_vb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c61g_vb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-1-duotone" {...props}></Icon>
