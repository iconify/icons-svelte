<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdtzjxbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdtzjxbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-export-fill" {...props}></Icon>
