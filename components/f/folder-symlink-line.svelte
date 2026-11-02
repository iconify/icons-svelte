<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnr__ybfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnr__ybfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-symlink-line" {...props}></Icon>
