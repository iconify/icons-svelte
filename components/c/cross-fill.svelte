<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3s94jb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3s94jb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cross-fill" {...props}></Icon>
