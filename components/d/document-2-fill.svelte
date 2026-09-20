<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kifu49xfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kifu49xfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:document-2-fill" {...props}></Icon>
