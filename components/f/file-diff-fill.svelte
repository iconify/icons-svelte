<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu6p-ybrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu6p-ybrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-diff-fill" {...props}></Icon>
