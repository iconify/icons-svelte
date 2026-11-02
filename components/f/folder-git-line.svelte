<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pil_10b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pil_10b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-git-line" {...props}></Icon>
