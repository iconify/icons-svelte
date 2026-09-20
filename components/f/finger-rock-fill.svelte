<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6erbx_3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6erbx_3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-rock-fill" {...props}></Icon>
